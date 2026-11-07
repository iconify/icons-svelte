<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s__fhe3nj.css';
import '../../css/t/tr0cf2bpt.css';
import '../../css/t/t-s7oqbld.css';
import '../../css/a/akyufm1qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s__fhe3nj"/><path class="tr0cf2bpt"/><path class="t-s7oqbld"/><path class="akyufm1qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pipette-bold-duotone" {...props}></Icon>
