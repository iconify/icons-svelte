<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzml2dbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qzml2dbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-question-fill" {...props}></Icon>
