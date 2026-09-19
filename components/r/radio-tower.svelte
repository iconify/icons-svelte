<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4ksqflca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t4ksqflca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:radio-tower" {...props}></Icon>
