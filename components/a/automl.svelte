<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx1_gabtl.css';
import '../../css/j/jk0rnfymy.css';
import '../../css/i/io_0phpjr.css';
import '../../css/f/fuatp5wib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx1_gabtl"/><path class="jk0rnfymy"/><path class="io_0phpjr"/><path class="fuatp5wib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:automl" {...props}></Icon>
