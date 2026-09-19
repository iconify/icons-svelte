<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpmydebry.css';
import '../../css/k/kgk78cbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpmydebry"/><path class="kgk78cbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:coin-insert" {...props}></Icon>
