<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt3vx2b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jt3vx2b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:at-circle-fill" {...props}></Icon>
