<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj_efqbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bj_efqbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:envelope" {...props}></Icon>
