<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c93967rjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c93967rjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heading-04" {...props}></Icon>
