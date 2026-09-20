<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpvnfjbpj.css';
import '../../css/a/a5arprq4h.css';
import '../../css/s/s88afubvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpvnfjbpj"/><path class="a5arprq4h"/><path class="s88afubvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:content-write" {...props}></Icon>
