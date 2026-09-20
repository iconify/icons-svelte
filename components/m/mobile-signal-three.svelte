<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_zxa9hzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_zxa9hzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mobile-signal-three" {...props}></Icon>
