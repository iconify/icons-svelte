<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx_sllbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fx_sllbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-egg" {...props}></Icon>
