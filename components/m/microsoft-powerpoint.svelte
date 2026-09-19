<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyyt5hbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nyyt5hbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:microsoft-powerpoint" {...props}></Icon>
