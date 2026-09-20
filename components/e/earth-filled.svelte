<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn9vt7btf.css';
import '../../css/r/ravm008iv.css';
import '../../css/u/uu72obc_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn9vt7btf"/><path class="ravm008iv"/><path class="uu72obc_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:earth-filled" {...props}></Icon>
