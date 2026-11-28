<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdawh-2am.css';
import '../../css/d/dcxarjboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdawh-2am secondary"/><path class="dcxarjboh primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:reply-arrow-duo" {...props}></Icon>
