<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmierzc3a.css';
import '../../css/t/t3qjwd-yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="lmierzc3a"/><path class="t3qjwd-yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:data-output" {...props}></Icon>
