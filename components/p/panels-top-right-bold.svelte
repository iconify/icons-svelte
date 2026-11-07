<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-tu9rzsd.css';
import '../../css/m/mnd7hcbix.css';
import '../../css/k/k-q3_rj-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-tu9rzsd"/><path class="mnd7hcbix"/><path clip-rule="evenodd" class="k-q3_rj-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-top-right-bold" {...props}></Icon>
