<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xehkvvg-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xehkvvg-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:navigation-48-bold" {...props}></Icon>
