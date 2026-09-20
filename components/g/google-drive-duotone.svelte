<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo_eecq-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo_eecq-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:google-drive-duotone" {...props}></Icon>
