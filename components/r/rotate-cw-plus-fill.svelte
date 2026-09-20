<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clp786bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clp786bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:rotate-cw-plus-fill" {...props}></Icon>
