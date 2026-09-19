<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loga5ub-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loga5ub-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:grill-charcoal" {...props}></Icon>
