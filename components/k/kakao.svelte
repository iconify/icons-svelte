<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsl7p9qal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsl7p9qal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kakao" {...props}></Icon>
