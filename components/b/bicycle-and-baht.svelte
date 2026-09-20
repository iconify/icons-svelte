<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_pwiya-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v_pwiya-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-and-baht" {...props}></Icon>
