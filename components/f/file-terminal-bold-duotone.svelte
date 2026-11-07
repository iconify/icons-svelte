<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj6gwrmjs.css';
import '../../css/f/ffwd6obzr.css';
import '../../css/o/o0qlb2nqx.css';
import '../../css/q/q2ycdab-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path class="ffwd6obzr"/><path class="o0qlb2nqx"/><path class="q2ycdab-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-terminal-bold-duotone" {...props}></Icon>
