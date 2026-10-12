<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnvtau33l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vnvtau33l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:logo-google-drive-20" {...props}></Icon>
