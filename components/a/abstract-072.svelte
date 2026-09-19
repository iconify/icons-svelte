<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzlh_1qrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bzlh_1qrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-072" {...props}></Icon>
