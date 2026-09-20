<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg-f40bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg-f40bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:fire-extinguisher" {...props}></Icon>
