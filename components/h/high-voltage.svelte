<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy42rxa0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qy42rxa0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:high-voltage" {...props}></Icon>
