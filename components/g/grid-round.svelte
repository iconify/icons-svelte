<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex3o1inzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex3o1inzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:grid-round" {...props}></Icon>
