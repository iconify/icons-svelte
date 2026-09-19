<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgcb9zw2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lgcb9zw2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pointer-down" {...props}></Icon>
