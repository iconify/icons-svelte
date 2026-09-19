<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc1-cb1mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc1-cb1mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:caret-circle-down" {...props}></Icon>
