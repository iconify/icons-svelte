<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zjlx72b5f.css';
import '../../css/h/hyxdxwsmj.css';
import '../../css/g/grur7igsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="zjlx72b5f"/><path clip-rule="evenodd" class="hyxdxwsmj"/><path class="grur7igsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:backup" {...props}></Icon>
