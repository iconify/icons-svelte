<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn0_e_zgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rn0_e_zgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:incognito" {...props}></Icon>
