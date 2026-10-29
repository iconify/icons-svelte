<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q65jjqyob.css';
import '../../css/k/k_n9znbon.css';
import '../../css/j/jmvv3kbnk.css';
import '../../css/y/ykqnlnbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="q65jjqyob"/><path class="k_n9znbon wm-a"/><path class="jmvv3kbnk"/><path class="wm-a ykqnlnbbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-check-duo" {...props}></Icon>
