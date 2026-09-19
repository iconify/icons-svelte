<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s88sv1bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":350,"height":512};
const content = `<path class="s88sv1bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:hack" {...props}></Icon>
