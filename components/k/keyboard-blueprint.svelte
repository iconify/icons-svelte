<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/o/o5v6yuw3m.css';
import '../../css/a/ae-w54boi.css';
import '../../css/c/cd2d17stg.css';
import '../../css/n/nl8u9ehql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="o5v6yuw3m wm-deco"/><path class="ae-w54boi wm-deco"/><path class="cd2d17stg wm-k"/><path class="nl8u9ehql wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:keyboard-blueprint" {...props}></Icon>
