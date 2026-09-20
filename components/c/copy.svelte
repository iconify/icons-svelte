<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko0b56bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko0b56bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:copy" {...props}></Icon>
