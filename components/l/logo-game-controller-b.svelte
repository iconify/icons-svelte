<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji4dzvl8f.css';
import '../../css/b/bzl494b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ji4dzvl8f"/><path class="bzl494b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-game-controller-b" {...props}></Icon>
