<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoleo-byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="eoleo-byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:delicious" {...props}></Icon>
