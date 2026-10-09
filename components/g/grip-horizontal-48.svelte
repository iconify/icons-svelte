<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_szgrglp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s_szgrglp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grip-horizontal-48" {...props}></Icon>
