<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l21du2bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l21du2bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gold-bar-48" {...props}></Icon>
