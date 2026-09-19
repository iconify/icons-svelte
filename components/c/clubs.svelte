<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8fsvbcnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j8fsvbcnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:clubs" {...props}></Icon>
