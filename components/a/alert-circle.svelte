<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_ge0h55x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s_ge0h55x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:alert-circle" {...props}></Icon>
