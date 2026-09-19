<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir17xnytb.css';
import '../../css/b/b949_hboo.css';
import '../../css/t/tsjlmkb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ir17xnytb"/><path class="b949_hboo duoicon-primary-layer"/><path class="duoicon-secondary-layer tsjlmkb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:app" {...props}></Icon>
