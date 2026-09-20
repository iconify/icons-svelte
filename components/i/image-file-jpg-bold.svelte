<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stdec_j8d.css';
import '../../css/j/jryo535wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stdec_j8d"/><path class="jryo535wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:image-file-jpg-bold" {...props}></Icon>
