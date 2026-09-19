<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me234t_fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="me234t_fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:attached-shield" {...props}></Icon>
