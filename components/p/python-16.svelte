<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no9uvky3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="no9uvky3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:python-16" {...props}></Icon>
