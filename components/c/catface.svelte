<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn8j0-frr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gn8j0-frr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:catface" {...props}></Icon>
