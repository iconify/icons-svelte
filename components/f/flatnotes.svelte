<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcbi2lbyp.css';
import '../../css/i/ixp_5jg3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kcbi2lbyp"/><path class="ixp_5jg3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flatnotes" {...props}></Icon>
