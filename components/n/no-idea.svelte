<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiiflsbvw.css';
import '../../css/c/c6br4ybmr.css';
import '../../css/b/b0d8i51hx.css';
import '../../css/e/engdf_brx.css';
import '../../css/w/wcirrbcym.css';
import '../../css/o/o0xw4kbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hiiflsbvw"/><path class="c6br4ybmr"/><circle class="b0d8i51hx"/><path class="engdf_brx"/><path class="wcirrbcym"/><path class="o0xw4kbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:no-idea" {...props}></Icon>
