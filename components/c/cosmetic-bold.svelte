<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oks3xobbp.css';
import '../../css/w/wsook6b4e.css';
import '../../css/a/ansc4kbhg.css';
import '../../css/w/wkq9lk8hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oks3xobbp"/><path class="wsook6b4e"/><path class="ansc4kbhg"/><path class="wkq9lk8hk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cosmetic-bold" {...props}></Icon>
