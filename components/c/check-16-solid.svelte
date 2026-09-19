<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz6foib1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iz6foib1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:check-16-solid" {...props}></Icon>
