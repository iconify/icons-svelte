<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgn5slbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgn5slbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:chevron-up" {...props}></Icon>
