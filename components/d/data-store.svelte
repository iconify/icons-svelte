<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v24ihwb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="v24ihwb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:data-store" {...props}></Icon>
