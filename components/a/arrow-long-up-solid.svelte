<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq7r5obcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tq7r5obcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-long-up-solid" {...props}></Icon>
