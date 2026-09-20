<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftit3v5he.css';
import '../../css/f/ffalivcqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ftit3v5he"/><circle class="ffalivcqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crontab-guru" {...props}></Icon>
