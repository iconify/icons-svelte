<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4imvxbfg.css';
import '../../css/p/pdqwe3x1i.css';
import '../../css/a/a2shhjbqb.css';
import '../../css/e/eldq07ydi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s4imvxbfg"/><path class="pdqwe3x1i"/><path class="a2shhjbqb"/><path class="eldq07ydi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubecraft" {...props}></Icon>
