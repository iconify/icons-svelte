<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2fnp9guc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2fnp9guc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:global-education" {...props}></Icon>
