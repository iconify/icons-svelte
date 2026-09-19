<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9t5qgbnj.css';
import '../../css/u/uqsh6ibhf.css';
import '../../css/t/twp4zob4x.css';
import '../../css/v/vox0oqb1v.css';
import '../../css/q/qeol496zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x9t5qgbnj"/><path class="uqsh6ibhf"/><circle class="twp4zob4x"/><circle class="vox0oqb1v"/><circle class="qeol496zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:privacy" {...props}></Icon>
