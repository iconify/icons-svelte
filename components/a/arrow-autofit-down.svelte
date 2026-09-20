<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl7u8lp9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl7u8lp9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-autofit-down" {...props}></Icon>
