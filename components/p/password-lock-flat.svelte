<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zbqsdtbha.css';
import '../../css/e/efzf-24zr.css';
import '../../css/o/o43u-8z7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zbqsdtbha"/><path class="efzf-24zr"/><path class="o43u-8z7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:password-lock-flat" {...props}></Icon>
