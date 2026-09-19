<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grmnn1biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":544,"height":472};
const content = `<path class="grmnn1biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:image" {...props}></Icon>
