<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/kkm7v7wlq.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/x/xxwofqeju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="kkm7v7wlq wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="xxwofqeju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-top-blueprint" {...props}></Icon>
