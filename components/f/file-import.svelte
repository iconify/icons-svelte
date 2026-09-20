<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p07tmccvv.css';
import '../../css/o/o0s3prb3b.css';
import '../../css/h/h5i3i5jgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="p07tmccvv"><path class="o0s3prb3b"/><path class="h5i3i5jgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-import" {...props}></Icon>
