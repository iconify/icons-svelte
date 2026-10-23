<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c45eqgb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c45eqgb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:half-note" {...props}></Icon>
