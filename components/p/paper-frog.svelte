<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9u55vzlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g9u55vzlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paper-frog" {...props}></Icon>
