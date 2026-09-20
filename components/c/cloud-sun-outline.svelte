<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slz8b_t7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="slz8b_t7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-sun-outline" {...props}></Icon>
