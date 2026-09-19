<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3-nd4bnk.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/f/fiavfxncv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3-nd4bnk"/><path class="bwibdw4bb"/><path class="fiavfxncv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:equal-circle" {...props}></Icon>
