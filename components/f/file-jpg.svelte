<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/j/jcxlm2b2l.css';
import '../../css/a/ar-7x19wi.css';
import '../../css/z/zjh4xye2a.css';
import '../../css/s/smxdsl_uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="jcxlm2b2l"/><path class="ar-7x19wi"/><path class="zjh4xye2a"/><path class="smxdsl_uu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:file-jpg" {...props}></Icon>
