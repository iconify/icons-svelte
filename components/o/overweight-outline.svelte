<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_6hrubaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n_6hrubaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:overweight-outline" {...props}></Icon>
