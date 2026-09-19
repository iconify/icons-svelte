<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc4yxhbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":819,"height":638};
const content = `<path class="vc4yxhbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:group" {...props}></Icon>
