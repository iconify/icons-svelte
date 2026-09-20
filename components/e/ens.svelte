<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9htj8btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9htj8btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ens" {...props}></Icon>
