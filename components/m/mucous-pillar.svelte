<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mak8fzbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mak8fzbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mucous-pillar" {...props}></Icon>
