<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqzxaygky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqzxaygky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:letter-japanese-a" {...props}></Icon>
