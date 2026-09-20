<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko59n4btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ko59n4btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:forward-square-f" {...props}></Icon>
