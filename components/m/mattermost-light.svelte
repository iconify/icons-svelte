<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj1vc8a4f.css';
import '../../css/g/gi4a4pb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":501,"height":501};
const content = `<path class="lj1vc8a4f"/><path class="gi4a4pb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mattermost-light" {...props}></Icon>
