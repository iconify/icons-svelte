<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3bzb4bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3bzb4bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-less-than-or-equal" {...props}></Icon>
