<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy2zsfmxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy2zsfmxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:relation-many-to-many-filled" {...props}></Icon>
