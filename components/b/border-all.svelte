<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf4bdhbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vf4bdhbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:border-all" {...props}></Icon>
