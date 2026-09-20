<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0m-cfizf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0m-cfizf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-bottom-dashed" {...props}></Icon>
