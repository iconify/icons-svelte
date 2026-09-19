<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk7827bhk.css';
import '../../css/d/dkh-5rbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk7827bhk"/><path class="dkh-5rbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-cloud-rain" {...props}></Icon>
