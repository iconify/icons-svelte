<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0bcgbc_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0bcgbc_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:error-warning-fill" {...props}></Icon>
