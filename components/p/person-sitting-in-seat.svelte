<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw4e8vbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cw4e8vbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sitting-in-seat" {...props}></Icon>
