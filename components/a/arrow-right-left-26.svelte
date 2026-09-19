<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fctujlv1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="fctujlv1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-right-left-26" {...props}></Icon>
