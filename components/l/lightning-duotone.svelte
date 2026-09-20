<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtsnveitd.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vt533fbwo.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/n/nteqkgdxx.css';
import '../../css/a/aisxi3qis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGabXJgcxD" class="vtsnveitd"/></defs><g class="cuyn6tgcc"><path clip-rule="evenodd" class="vt533fbwo"/><use href="#SVGabXJgcxD" clip-rule="evenodd" class="d2kvgvbvc"/><path class="nteqkgdxx"/><use href="#SVGabXJgcxD" clip-rule="evenodd" class="d2kvgvbvc"/><path class="aisxi3qis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lightning-duotone" {...props}></Icon>
