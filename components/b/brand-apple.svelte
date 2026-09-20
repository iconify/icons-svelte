<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac_spac3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac_spac3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-apple" {...props}></Icon>
