<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifilj8bay.css';
import '../../css/v/vw71kgb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifilj8bay"/><path clip-rule="evenodd" class="vw71kgb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-russian-ruble-filled" {...props}></Icon>
