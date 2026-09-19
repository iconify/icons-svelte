<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwl-77ffc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwl-77ffc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:format-indent-increase" {...props}></Icon>
