<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_f6jmvbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m_f6jmvbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:red-exclamation-mark" {...props}></Icon>
