<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg68m81-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":27};
const content = `<path class="qg68m81-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:check" {...props}></Icon>
