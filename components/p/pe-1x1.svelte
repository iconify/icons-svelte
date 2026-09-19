<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5wf9mbzr.css';
import '../../css/o/o0r6dnbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5wf9mbzr"/><path class="o0r6dnbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:pe-1x1" {...props}></Icon>
