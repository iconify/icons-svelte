<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-du2rb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q-du2rb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:grid" {...props}></Icon>
