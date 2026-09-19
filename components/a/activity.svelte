<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aton4b70c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aton4b70c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:activity" {...props}></Icon>
