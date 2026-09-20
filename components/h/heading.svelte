<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeruo7bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeruo7bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heading" {...props}></Icon>
