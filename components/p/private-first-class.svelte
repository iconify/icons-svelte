<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh_971ftw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vh_971ftw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:private-first-class" {...props}></Icon>
