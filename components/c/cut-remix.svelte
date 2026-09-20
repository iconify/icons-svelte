<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suedpgeak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="suedpgeak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cut-remix" {...props}></Icon>
