<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_fy29box.css';
import '../../css/q/qlvc8z3kf.css';
import '../../css/x/xcefx3l9e.css';
import '../../css/c/cf1g6vc0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_fy29box"/><path class="qlvc8z3kf"/><path class="xcefx3l9e"/><path clip-rule="evenodd" class="cf1g6vc0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bot-outline" {...props}></Icon>
