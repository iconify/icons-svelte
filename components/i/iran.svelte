<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1x_6zbkv.css';
import '../../css/s/s22y7z9os.css';
import '../../css/y/yhov8zbzn.css';
import '../../css/d/dyfumibih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="s22y7z9os"/><path class="yhov8zbzn"/><path class="dyfumibih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:iran" {...props}></Icon>
