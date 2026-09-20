<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf--c0vyf.css';
import '../../css/z/z72r2ab5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf--c0vyf"/><path class="z72r2ab5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bitget" {...props}></Icon>
