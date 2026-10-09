<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw3xaacjo.css';
import '../../css/l/lr6wkxb-c.css';
import '../../css/a/a7fphlb5n.css';
import '../../css/t/tvv7gjyas.css';
import '../../css/t/tooldrzdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="lr6wkxb-c"/><path class="a7fphlb5n"/><path class="tvv7gjyas"/><path class="tooldrzdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:accessibility-20" {...props}></Icon>
