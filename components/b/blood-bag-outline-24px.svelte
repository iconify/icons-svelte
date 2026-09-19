<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmf952b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmf952b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-bag-outline-24px" {...props}></Icon>
