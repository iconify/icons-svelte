<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5l9kaceg.css';
import '../../css/w/wao3ae53h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5l9kaceg"/><path class="wao3ae53h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:medical-case" {...props}></Icon>
