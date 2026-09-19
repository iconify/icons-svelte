<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9rwhqbjf.css';
import '../../css/j/jlqtr1aep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s9rwhqbjf"/><path class="jlqtr1aep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:biohazard" {...props}></Icon>
