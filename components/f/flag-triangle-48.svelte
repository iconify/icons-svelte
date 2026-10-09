<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-0gtd2mz.css';
import '../../css/f/f79__7b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a-0gtd2mz"/><path class="f79__7b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flag-triangle-48" {...props}></Icon>
