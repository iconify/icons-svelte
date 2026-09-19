<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3o6v3kfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3o6v3kfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:asterisk" {...props}></Icon>
