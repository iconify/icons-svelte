<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk7f85f6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="jk7f85f6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:align-center" {...props}></Icon>
