<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qott8t_wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qott8t_wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:radioactive-1-remix" {...props}></Icon>
