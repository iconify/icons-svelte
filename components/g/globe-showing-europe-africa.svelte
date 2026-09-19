<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pn4nwmbpt.css';
import '../../css/l/lul-6ye9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="pn4nwmbpt"/><path clip-rule="evenodd" class="lul-6ye9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:globe-showing-europe-africa" {...props}></Icon>
