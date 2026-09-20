<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y50-e9bsi.css';
import '../../css/i/i2s29ccsd.css';
import '../../css/j/jzlsh2blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y50-e9bsi"/><path class="i2s29ccsd"/><path class="jzlsh2blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:grid-ruler" {...props}></Icon>
