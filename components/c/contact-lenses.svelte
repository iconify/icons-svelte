<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fc0i6jz9j.css';
import '../../css/u/ujlvc1bor.css';
import '../../css/b/b5f5xnbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fc0i6jz9j"/><path class="ujlvc1bor"/><path class="b5f5xnbyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contact-lenses" {...props}></Icon>
