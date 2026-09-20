<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7b62qu9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7b62qu9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:blogger" {...props}></Icon>
