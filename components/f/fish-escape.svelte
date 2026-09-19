<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phau6domw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="phau6domw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fish-escape" {...props}></Icon>
