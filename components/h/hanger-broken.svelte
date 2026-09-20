<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io9pepb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io9pepb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hanger-broken" {...props}></Icon>
