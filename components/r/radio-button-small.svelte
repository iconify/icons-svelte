<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2v5x-bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="u2v5x-bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:radio-button-small" {...props}></Icon>
