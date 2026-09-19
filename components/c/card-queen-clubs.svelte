<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etdo7y9jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="etdo7y9jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-queen-clubs" {...props}></Icon>
