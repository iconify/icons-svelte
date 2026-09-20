<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxs-f7bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxs-f7bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-vertical-fill" {...props}></Icon>
