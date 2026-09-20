<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z80t8obne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z80t8obne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:hand-holding-dollar" {...props}></Icon>
