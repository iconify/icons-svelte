<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwv-pjobw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gwv-pjobw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:exclamation-triangle-16-solid" {...props}></Icon>
