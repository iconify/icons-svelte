<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx0jmzb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qx0jmzb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:devices-apps" {...props}></Icon>
