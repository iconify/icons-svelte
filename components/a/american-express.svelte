<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyugebdld.css';
import '../../css/w/w238-db3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nyugebdld"/><path class="w238-db3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:american-express" {...props}></Icon>
