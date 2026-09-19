<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oafi4yb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oafi4yb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:head-filled" {...props}></Icon>
