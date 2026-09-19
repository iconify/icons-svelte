<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg8xfks_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gg8xfks_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:plus" {...props}></Icon>
