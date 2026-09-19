<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8kl_xhhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8kl_xhhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:linkedin-v1-fill" {...props}></Icon>
