<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkxtprlip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkxtprlip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-dropbox-outline" {...props}></Icon>
