<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/l005-rw7v.css';
import '../../css/d/d-e424q9g.css';
import '../../css/f/ftoxqwbpl.css';
import '../../css/b/byt_zx-un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="l005-rw7v"/><circle class="d-e424q9g"/><circle class="ftoxqwbpl"/><path class="byt_zx-un"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bike" {...props}></Icon>
