<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cisvadb6a.css';
import '../../css/y/y-864bbjp.css';
import '../../css/v/v71jzsb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cisvadb6a"/><path class="y-864bbjp"/><path class="v71jzsb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:double-glazing-48-bold" {...props}></Icon>
