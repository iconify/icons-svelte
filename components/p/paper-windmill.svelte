<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz5y-8bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gz5y-8bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paper-windmill" {...props}></Icon>
