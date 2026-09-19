<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvw6yy-du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvw6yy-du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:garage" {...props}></Icon>
