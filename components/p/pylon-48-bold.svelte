<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9x5rac2h.css';
import '../../css/o/o63gs7ffv.css';
import '../../css/n/ne8de7own.css';
import '../../css/h/hfvtdh7cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q9x5rac2h"/><path class="o63gs7ffv"/><path class="ne8de7own"/><path class="hfvtdh7cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pylon-48-bold" {...props}></Icon>
