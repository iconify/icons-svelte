<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrn6mdb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrn6mdb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:greater-than-equal" {...props}></Icon>
