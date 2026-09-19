<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-6d7pbcl.css';
import '../../css/x/x4pv4iirw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b-6d7pbcl"/><path class="x4pv4iirw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cost-total" {...props}></Icon>
