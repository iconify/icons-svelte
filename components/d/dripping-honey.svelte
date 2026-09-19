<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvkgz2bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qvkgz2bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dripping-honey" {...props}></Icon>
