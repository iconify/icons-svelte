<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko0wxuwmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko0wxuwmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-drizzle" {...props}></Icon>
