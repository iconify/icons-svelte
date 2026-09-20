<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxzv7ug8a.css';
import '../../css/g/gam-p8bqe.css';
import '../../css/e/ece3hyfmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxzv7ug8a"/><path class="gam-p8bqe"/><path class="ece3hyfmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cbeth" {...props}></Icon>
