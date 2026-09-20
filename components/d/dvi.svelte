<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg77lubaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cg77lubaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dvi" {...props}></Icon>
