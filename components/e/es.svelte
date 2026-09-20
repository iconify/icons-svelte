<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi2203rfe.css';
import '../../css/p/pl1wuvfgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi2203rfe"/><path class="pl1wuvfgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:es" {...props}></Icon>
