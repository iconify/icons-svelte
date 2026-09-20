<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlq4g9a-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jlq4g9a-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:picnic-shelter" {...props}></Icon>
