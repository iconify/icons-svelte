<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebp_ucbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebp_ucbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-tencentmeeting" {...props}></Icon>
