<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdep0-bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdep0-bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-broken" {...props}></Icon>
