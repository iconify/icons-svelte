<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/t/tmhs8r1ps.css';
import '../../css/d/d_xs8tbkb.css';
import '../../css/b/bf3cxvlkw.css';
import '../../css/r/rh9qoibkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="tmhs8r1ps"/><path class="d_xs8tbkb wm-shine"/><path class="bf3cxvlkw"/><path class="rh9qoibkn wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:git-commit" {...props}></Icon>
