<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib_u0zbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ib_u0zbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:person-add-16" {...props}></Icon>
