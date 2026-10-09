<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2_8-nb1y.css';
import '../../css/f/fbgnz0ewn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n2_8-nb1y"/><path class="fbgnz0ewn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:briefcase-20" {...props}></Icon>
