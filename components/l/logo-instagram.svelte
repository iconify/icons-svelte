<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk_t5kymf.css';
import '../../css/m/m1idjh0xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fk_t5kymf"/><path class="m1idjh0xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-instagram" {...props}></Icon>
