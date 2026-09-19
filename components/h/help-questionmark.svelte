<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxv55ebri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxv55ebri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:help-questionmark" {...props}></Icon>
