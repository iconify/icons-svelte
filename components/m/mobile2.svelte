<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9xu63h9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s9xu63h9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:mobile2" {...props}></Icon>
