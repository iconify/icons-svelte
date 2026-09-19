<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhqbhisui.css';
import '../../css/j/jvlxhcclc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nhqbhisui"/><path class="jvlxhcclc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:mahjong" {...props}></Icon>
