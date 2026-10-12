<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyyw2ejbf.css';
import '../../css/c/cdzkw9bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lyyw2ejbf"/><path class="cdzkw9bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brain-20" {...props}></Icon>
