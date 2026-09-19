<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxvrc-n9x.css';
import '../../css/w/wtfir1bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="fxvrc-n9x"/><path class="wtfir1bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-shield" {...props}></Icon>
