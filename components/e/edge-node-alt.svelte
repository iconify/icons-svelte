<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3aaqabzw.css';
import '../../css/t/tl0s0vbfd.css';
import '../../css/o/o-jkj3has.css';
import '../../css/h/hn160mbff.css';
import '../../css/z/zd7flj3zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m3aaqabzw"/><circle class="tl0s0vbfd"/><circle class="o-jkj3has"/><circle class="hn160mbff"/><path class="zd7flj3zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:edge-node-alt" {...props}></Icon>
