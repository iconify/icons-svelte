<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3az1bq5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e3az1bq5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bomber" {...props}></Icon>
