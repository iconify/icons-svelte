<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kackdgatl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kackdgatl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-arrow-up-solid" {...props}></Icon>
