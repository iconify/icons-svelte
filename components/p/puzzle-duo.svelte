<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m60pqtldl.css';
import '../../css/s/sui4_vb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m60pqtldl secondary"/><path class="primary sui4_vb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:puzzle-duo" {...props}></Icon>
