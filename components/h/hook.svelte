<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyleo_4xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wyleo_4xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:hook" {...props}></Icon>
