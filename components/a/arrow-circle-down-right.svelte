<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhe7-4bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhe7-4bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-circle-down-right" {...props}></Icon>
