<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmblh-wku.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bckwe4qia.css';
import '../../css/e/eg485t5kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmblh-wku secondary"/><g class="dt0cm9dhy primary"><path class="bckwe4qia"/><path class="eg485t5kb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:key-round-duo" {...props}></Icon>
