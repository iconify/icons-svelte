<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3jm3bc0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3jm3bc0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pregnant-24px" {...props}></Icon>
