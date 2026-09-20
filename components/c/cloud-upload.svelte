<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko8ntx8ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko8ntx8ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-upload" {...props}></Icon>
