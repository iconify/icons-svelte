<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yws5cp5zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yws5cp5zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:logout" {...props}></Icon>
