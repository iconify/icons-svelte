<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5lgt4bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5lgt4bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:audio-file-bold" {...props}></Icon>
