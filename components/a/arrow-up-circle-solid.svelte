<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikyj-rbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ikyj-rbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-circle-solid" {...props}></Icon>
