<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u5ss79pzi.css';
import '../../css/z/znsgree8n.css';
import '../../css/x/xceiv6bnm.css';
import '../../css/y/y00xw2byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="u5ss79pzi"/><path class="znsgree8n"/><path clip-rule="evenodd" class="xceiv6bnm"/><path class="y00xw2byu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:circle-four-line" {...props}></Icon>
