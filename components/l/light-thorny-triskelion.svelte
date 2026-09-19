<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csit38b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="csit38b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:light-thorny-triskelion" {...props}></Icon>
