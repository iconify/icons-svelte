<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4z1ldb0q.css';
import '../../css/o/oj6gwrmjs.css';
import '../../css/g/gvp-p5blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4z1ldb0q"/><path clip-rule="evenodd" class="oj6gwrmjs"/><path class="gvp-p5blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-audio-bold-duotone" {...props}></Icon>
