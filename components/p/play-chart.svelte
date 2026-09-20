<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrv6xysju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrv6xysju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:play-chart" {...props}></Icon>
