<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx-pl7guj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx-pl7guj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-undo-down-right" {...props}></Icon>
