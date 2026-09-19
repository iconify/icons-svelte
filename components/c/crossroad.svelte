<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydt4-bcup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ydt4-bcup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crossroad" {...props}></Icon>
