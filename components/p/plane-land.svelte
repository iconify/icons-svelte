<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naz42fb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="naz42fb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plane-land" {...props}></Icon>
