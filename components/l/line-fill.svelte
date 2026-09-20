<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz78ohduh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz78ohduh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:line-fill" {...props}></Icon>
