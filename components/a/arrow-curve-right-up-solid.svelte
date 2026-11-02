<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1t3o4bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1t3o4bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-right-up-solid" {...props}></Icon>
