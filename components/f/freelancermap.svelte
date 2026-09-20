<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h62w_cc4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h62w_cc4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:freelancermap" {...props}></Icon>
