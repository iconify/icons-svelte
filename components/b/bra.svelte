<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uptmd1bpv.css';
import '../../css/j/j4razejqy.css';
import '../../css/n/n0zdkcb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="uptmd1bpv"/><path class="j4razejqy"/><path class="n0zdkcb4w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bra" {...props}></Icon>
