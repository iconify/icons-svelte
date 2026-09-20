<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgxek2uzm.css';
import '../../css/r/rneb_3caj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgxek2uzm"/><circle class="rneb_3caj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:info-outline" {...props}></Icon>
