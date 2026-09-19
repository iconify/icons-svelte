<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agq-2qutk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="agq-2qutk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-red-hat-ai-instructlab-on-ibm-cloud" {...props}></Icon>
