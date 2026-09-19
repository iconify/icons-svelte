<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j11rv3zxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j11rv3zxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:heading" {...props}></Icon>
