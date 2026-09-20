<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2fyht4an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n2fyht4an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-alerting" {...props}></Icon>
