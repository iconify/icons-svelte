<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmf_k48cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmf_k48cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:building-alt-04" {...props}></Icon>
