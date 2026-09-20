<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx4-jk-hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx4-jk-hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-long-fill" {...props}></Icon>
