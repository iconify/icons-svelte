<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rex75jb-y.css';
import '../../css/c/cv_qrx7lo.css';
import '../../css/k/kn5t4v-6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rex75jb-y"/><path class="cv_qrx7lo"/><path class="kn5t4v-6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bitkub-chain" {...props}></Icon>
