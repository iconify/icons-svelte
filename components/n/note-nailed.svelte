<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3sut03us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="k3sut03us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:note-nailed" {...props}></Icon>
