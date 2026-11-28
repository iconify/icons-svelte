<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/y57400b9h.css';
import '../../css/b/bue-mrlhv.css';
import '../../css/v/v5wkezbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="y57400b9h"/><path class="bue-mrlhv"/><path class="v5wkezbbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-right-line-duo" {...props}></Icon>
