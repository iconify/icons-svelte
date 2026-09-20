<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-k3b0q2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b-k3b0q2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cloud-download-o" {...props}></Icon>
