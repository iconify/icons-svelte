<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p07tmccvv.css';
import '../../css/u/ufffrnb-r.css';
import '../../css/h/hdgdwjbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="p07tmccvv"><path class="ufffrnb-r"/><path class="hdgdwjbgw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-attachment" {...props}></Icon>
