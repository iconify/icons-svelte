<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyqu36w3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyqu36w3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hbo" {...props}></Icon>
