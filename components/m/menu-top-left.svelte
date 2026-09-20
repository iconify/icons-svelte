<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaaeg5bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="qaaeg5bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:menu-top-left" {...props}></Icon>
