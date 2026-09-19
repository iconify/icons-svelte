<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7mdh3bqy.css';
import '../../css/q/qvisowbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i7mdh3bqy"/><path class="qvisowbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:copy" {...props}></Icon>
