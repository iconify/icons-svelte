<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_c3lsbki.css';
import '../../css/g/gs5s95byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x_c3lsbki"/><path class="gs5s95byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:python-solid" {...props}></Icon>
