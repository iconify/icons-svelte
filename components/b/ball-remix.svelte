<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awhr4eq_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="awhr4eq_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:ball-remix" {...props}></Icon>
