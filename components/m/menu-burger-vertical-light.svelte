<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7kfgg1tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7kfgg1tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-burger-vertical-light" {...props}></Icon>
