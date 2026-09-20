<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd4f1zkyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wd4f1zkyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:peertube-fill-24" {...props}></Icon>
