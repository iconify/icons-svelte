<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb1dfb9ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tb1dfb9ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:clothes-sweater" {...props}></Icon>
