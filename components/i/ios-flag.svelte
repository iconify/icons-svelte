<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3djcx2jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u3djcx2jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-flag" {...props}></Icon>
