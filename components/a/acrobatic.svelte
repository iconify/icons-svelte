<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh0m0cy5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uh0m0cy5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:acrobatic" {...props}></Icon>
