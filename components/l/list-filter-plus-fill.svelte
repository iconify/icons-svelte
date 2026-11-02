<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_l5jb__u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_l5jb__u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-filter-plus-fill" {...props}></Icon>
