<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g1te_5jwk.css';
import '../../css/e/ey8poua1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g1te_5jwk"/><path class="ey8poua1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:performing-arts" {...props}></Icon>
