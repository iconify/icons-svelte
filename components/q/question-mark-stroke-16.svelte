<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhpmsjbax.css';
import '../../css/t/t-jbtsufb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="qhpmsjbax"/><path class="t-jbtsufb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:question-mark-stroke-16" {...props}></Icon>
