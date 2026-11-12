<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_as2wbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_as2wbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pgadmin" {...props}></Icon>
