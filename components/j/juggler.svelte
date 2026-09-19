<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp_cxtxka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hp_cxtxka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:juggler" {...props}></Icon>
