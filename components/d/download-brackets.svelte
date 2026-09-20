<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf-k8abmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vf-k8abmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:download-brackets" {...props}></Icon>
