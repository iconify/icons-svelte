<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxnb46bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cxnb46bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:radio-unchecked" {...props}></Icon>
