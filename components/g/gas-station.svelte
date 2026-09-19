<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7ieandgj.css';
import '../../css/q/qcw0owpxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g7ieandgj"/><path class="qcw0owpxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gas-station" {...props}></Icon>
