<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czh5ncche.css';
import '../../css/c/chx9uvzml.css';
import '../../css/o/ox5-scb3j.css';
import '../../css/g/gy5pnuxbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="czh5ncche"/><path class="chx9uvzml"/><circle class="ox5-scb3j"/><circle class="gy5pnuxbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:rosette" {...props}></Icon>
