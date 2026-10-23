<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozg9a2b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ozg9a2b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-sterling-b2b-integration-saas" {...props}></Icon>
