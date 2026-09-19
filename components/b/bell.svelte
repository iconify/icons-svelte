<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izr86ab_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izr86ab_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell" {...props}></Icon>
