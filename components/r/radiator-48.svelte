<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8wvi4bxf.css';
import '../../css/q/qosg0qauw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j8wvi4bxf"/><path class="qosg0qauw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiator-48" {...props}></Icon>
