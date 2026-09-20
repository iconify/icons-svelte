<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vnbx2b2zx.css';
import '../../css/j/j8kuw0sgj.css';
import '../../css/f/fr98mpz8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vnbx2b2zx"/><path class="j8kuw0sgj"/><path clip-rule="evenodd" class="fr98mpz8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ghost-outline" {...props}></Icon>
