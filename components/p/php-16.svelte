<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrhi1hbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qrhi1hbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:php-16" {...props}></Icon>
