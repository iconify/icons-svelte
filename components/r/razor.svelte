<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hqc6zt2xp.css';
import '../../css/h/hcqjcgwzg.css';
import '../../css/w/wsg7qlbxr.css';
import '../../css/k/kbia9xb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="hqc6zt2xp"/><path class="hcqjcgwzg"/><path class="wsg7qlbxr"/><path class="kbia9xb4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:razor" {...props}></Icon>
