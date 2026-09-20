<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emnh37b7g.css';
import '../../css/z/zq6-f5buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emnh37b7g"/><path class="zq6-f5buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ctsi" {...props}></Icon>
