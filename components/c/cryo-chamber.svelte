<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk8gq0ufp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bk8gq0ufp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cryo-chamber" {...props}></Icon>
