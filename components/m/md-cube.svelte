<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjnbpgbsn.css';
import '../../css/f/fd5cwebhy.css';
import '../../css/h/h5uul4bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pjnbpgbsn"/><path class="fd5cwebhy"/><path class="h5uul4bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-cube" {...props}></Icon>
