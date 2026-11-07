<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbj6x5byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbj6x5byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-rounded-broken" {...props}></Icon>
