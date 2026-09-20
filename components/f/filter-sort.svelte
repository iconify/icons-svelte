<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mb0epnoxf.css';
import '../../css/h/h2kfwdbij.css';
import '../../css/e/eq0i8xhhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mb0epnoxf"/><path clip-rule="evenodd" class="h2kfwdbij"/><path class="eq0i8xhhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:filter-sort" {...props}></Icon>
