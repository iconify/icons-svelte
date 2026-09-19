<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egwr0nbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="egwr0nbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:object-ungroup" {...props}></Icon>
