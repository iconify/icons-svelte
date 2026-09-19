<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb_i9scyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="cb_i9scyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleloadertwo" {...props}></Icon>
