<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyynzkb6k.css';
import '../../css/c/c7maq1bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="pyynzkb6k"/><path class="c7maq1bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:airplay" {...props}></Icon>
