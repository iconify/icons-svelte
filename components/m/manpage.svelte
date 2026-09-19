<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbsf62b3k.css';
import '../../css/p/pwvlvn-7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hbsf62b3k"/><path class="pwvlvn-7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:manpage" {...props}></Icon>
