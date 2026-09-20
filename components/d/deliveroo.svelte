<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5xixwmin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5xixwmin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:deliveroo" {...props}></Icon>
