<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w91hv6pvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w91hv6pvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:color-picker" {...props}></Icon>
