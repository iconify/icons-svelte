<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv8dbcm4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv8dbcm4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gt" {...props}></Icon>
