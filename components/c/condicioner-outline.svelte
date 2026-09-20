<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnvucacag.css';
import '../../css/b/bh4frdbmf.css';
import '../../css/e/evzbml2ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnvucacag"/><path clip-rule="evenodd" class="bh4frdbmf"/><path class="evzbml2ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:condicioner-outline" {...props}></Icon>
