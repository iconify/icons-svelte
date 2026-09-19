<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbirz4byx.css';
import '../../css/c/c9buwng5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbirz4byx"/><path class="c9buwng5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-plus" {...props}></Icon>
