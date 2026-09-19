<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4yex3z8a.css';
import '../../css/u/uwvg1pb6m.css';
import '../../css/d/dlp7nstpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="a4yex3z8a"/><path class="uwvg1pb6m"/><circle class="dlp7nstpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hardware-security-module" {...props}></Icon>
