<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhha36vhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhha36vhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-bar-to-down-dashed" {...props}></Icon>
