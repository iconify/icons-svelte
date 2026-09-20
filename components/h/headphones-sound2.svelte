<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxm_0qbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxm_0qbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:headphones-sound2" {...props}></Icon>
