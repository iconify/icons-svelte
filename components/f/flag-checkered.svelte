<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boow2abii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boow2abii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-checkered" {...props}></Icon>
