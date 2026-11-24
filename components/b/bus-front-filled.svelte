<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-l2srbfo.css';
import '../../css/m/m-ub-lbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-l2srbfo"/><path clip-rule="evenodd" class="m-ub-lbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bus-front-filled" {...props}></Icon>
