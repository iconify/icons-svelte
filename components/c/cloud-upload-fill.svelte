<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_z7jbbuz.css';
import '../../css/g/gxjodwbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_z7jbbuz"/><path class="gxjodwbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:cloud-upload-fill" {...props}></Icon>
