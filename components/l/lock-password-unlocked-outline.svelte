<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bbujyitcz.css';
import '../../css/j/jwj5s6brs.css';
import '../../css/i/i3ujk8lbt.css';
import '../../css/f/f76vb05cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bbujyitcz"/><path class="jwj5s6brs"/><path class="i3ujk8lbt"/><path clip-rule="evenodd" class="f76vb05cy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-password-unlocked-outline" {...props}></Icon>
