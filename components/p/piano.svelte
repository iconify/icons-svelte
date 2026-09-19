<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow059ibzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ow059ibzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:piano" {...props}></Icon>
