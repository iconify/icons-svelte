<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kalrokb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="kalrokb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:creative-commons" {...props}></Icon>
