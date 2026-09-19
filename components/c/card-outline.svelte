<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k716ik9pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k716ik9pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:card-outline" {...props}></Icon>
