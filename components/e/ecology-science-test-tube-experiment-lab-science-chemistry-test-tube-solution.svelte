<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu3wysshd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wu3wysshd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ecology-science-test-tube-experiment-lab-science-chemistry-test-tube-solution" {...props}></Icon>
