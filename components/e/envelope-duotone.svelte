<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2wzvt0ia.css';
import '../../css/x/x5_n2lbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2wzvt0ia"/><path class="x5_n2lbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:envelope-duotone" {...props}></Icon>
