<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klcn6tchx.css';
import '../../css/n/ng1infulf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="klcn6tchx"/><path class="ng1infulf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pricetag-outline" {...props}></Icon>
