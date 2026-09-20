<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhl3owb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhl3owb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-3-bold" {...props}></Icon>
