<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5riambiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5riambiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-help-buoy" {...props}></Icon>
