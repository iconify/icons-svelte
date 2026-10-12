<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h54h6zbmm.css';
import '../../css/o/ob4kuqbkv.css';
import '../../css/u/uuz9mz48k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h54h6zbmm"/><path class="ob4kuqbkv"/><path class="uuz9mz48k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-pull-request-create-duotone" {...props}></Icon>
