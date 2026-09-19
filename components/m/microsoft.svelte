<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibge-kb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibge-kb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:microsoft" {...props}></Icon>
