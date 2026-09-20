<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uveq49prt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uveq49prt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crontab-guru-light" {...props}></Icon>
