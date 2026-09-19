<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl_msvlzl.css';
import '../../css/q/q6zptzlwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xl_msvlzl"/><path class="q6zptzlwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-elo-automotive-compliance" {...props}></Icon>
