<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k00210gyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k00210gyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pen" {...props}></Icon>
