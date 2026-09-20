<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpblc6xuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpblc6xuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rocketdotchat" {...props}></Icon>
