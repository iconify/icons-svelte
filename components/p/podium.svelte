<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w89ijc5ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w89ijc5ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:podium" {...props}></Icon>
