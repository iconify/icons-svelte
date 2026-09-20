<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge34bhbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge34bhbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-bolt" {...props}></Icon>
