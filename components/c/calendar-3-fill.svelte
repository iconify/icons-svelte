<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5ae-tbgb.css';
import '../../css/q/qeijpobfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5ae-tbgb"/><path class="qeijpobfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:calendar-3-fill" {...props}></Icon>
