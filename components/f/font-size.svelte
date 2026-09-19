<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkub0ab9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nkub0ab9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:font-size" {...props}></Icon>
