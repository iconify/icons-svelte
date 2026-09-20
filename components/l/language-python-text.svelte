<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv49kkb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv49kkb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:language-python-text" {...props}></Icon>
