<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbpfbqfii.css';
import '../../css/n/nrolmxo4x.css';
import '../../css/j/jophfjbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="mbpfbqfii"/><path class="nrolmxo4x"/><path class="jophfjbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:doctor" {...props}></Icon>
