<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eml8ybc8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eml8ybc8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:female-vampire" {...props}></Icon>
