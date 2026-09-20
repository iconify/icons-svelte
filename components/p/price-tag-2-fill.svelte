<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haca98uoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haca98uoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:price-tag-2-fill" {...props}></Icon>
