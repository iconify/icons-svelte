<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6z-3iz4b.css';
import '../../css/w/wpuyqmbtu.css';
import '../../css/l/ln93sbcwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":7,"height":16};
const content = `<circle class="m6z-3iz4b"/><circle class="wpuyqmbtu"/><circle class="ln93sbcwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:reorder" {...props}></Icon>
