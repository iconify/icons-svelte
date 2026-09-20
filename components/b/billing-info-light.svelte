<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zazwy-4qg.css';
import '../../css/i/iwtd4lopd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zazwy-4qg"/><path class="iwtd4lopd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:billing-info-light" {...props}></Icon>
