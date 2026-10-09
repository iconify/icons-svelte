<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atysxlblu.css';
import '../../css/g/g3wujfbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="atysxlblu"/><path class="g3wujfbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-schedule-48" {...props}></Icon>
