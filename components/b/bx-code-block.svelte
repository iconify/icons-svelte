<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz_8dhp3p.css';
import '../../css/v/v85x6e0bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz_8dhp3p"/><path class="v85x6e0bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-code-block" {...props}></Icon>
