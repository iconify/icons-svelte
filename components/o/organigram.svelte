<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdui4bc2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rdui4bc2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:organigram" {...props}></Icon>
