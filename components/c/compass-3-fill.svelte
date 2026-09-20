<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-0e2ykrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-0e2ykrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:compass-3-fill" {...props}></Icon>
