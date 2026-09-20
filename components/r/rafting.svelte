<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb-a7db1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="nb-a7db1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:rafting" {...props}></Icon>
