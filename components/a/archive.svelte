<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcploob5p.css';
import '../../css/y/yqi9zhbgt.css';
import '../../css/k/kjsax0b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcploob5p"/><path class="yqi9zhbgt"/><path class="kjsax0b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:archive" {...props}></Icon>
