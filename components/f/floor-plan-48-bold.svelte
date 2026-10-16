<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3k4bybje.css';
import '../../css/e/eo7syfsuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g3k4bybje"/><path class="eo7syfsuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:floor-plan-48-bold" {...props}></Icon>
