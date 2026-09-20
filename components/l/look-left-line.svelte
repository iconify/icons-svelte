<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ronm36v_x.css';
import '../../css/u/ukqa5ub-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ronm36v_x"/><path class="ukqa5ub-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:look-left-line" {...props}></Icon>
