<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioa832b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioa832b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:credly" {...props}></Icon>
