<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idqhxccai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="idqhxccai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:microscope-observation-sciene-remix" {...props}></Icon>
