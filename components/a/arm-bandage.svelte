<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmhvhqo9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gmhvhqo9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arm-bandage" {...props}></Icon>
