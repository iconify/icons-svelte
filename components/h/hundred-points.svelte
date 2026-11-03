<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grb84xddd.css';
import '../../css/w/wd-ix_sxa.css';
import '../../css/e/eh35uyflb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGrg9cCcwZ" class="grb84xddd"/></defs><use href="#SVGrg9cCcwZ" class="wd-ix_sxa"/><use href="#SVGrg9cCcwZ" class="eh35uyflb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:hundred-points" {...props}></Icon>
