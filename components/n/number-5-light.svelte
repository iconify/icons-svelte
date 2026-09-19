<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehuol1ywa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehuol1ywa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-5-light" {...props}></Icon>
