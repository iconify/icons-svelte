<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dojiukb8c.css';
import '../../css/u/u1_hubbvw.css';
import '../../css/w/wk2zli15y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dojiukb8c wm-k"/><path class="u1_hubbvw wm-a"/><path class="wk2zli15y wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:passport" {...props}></Icon>
