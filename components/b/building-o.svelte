<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayfjvlbde.css';
import '../../css/p/pb95qppxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ayfjvlbde"/><path class="pb95qppxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:building-o" {...props}></Icon>
