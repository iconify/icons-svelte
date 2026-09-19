<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9-03fbxk.css';
import '../../css/z/zwafnhb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9-03fbxk"/><path class="zwafnhb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:alarm-on" {...props}></Icon>
