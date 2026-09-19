<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w075n_c4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w075n_c4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:airgradient" {...props}></Icon>
