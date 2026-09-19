<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki9hr6bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki9hr6bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-left-outline" {...props}></Icon>
