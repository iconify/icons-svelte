<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlmscut1c.css';
import '../../css/s/sx9ljtq-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jlmscut1c"/><path class="sx9ljtq-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:audio" {...props}></Icon>
