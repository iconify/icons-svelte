<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljr8ztagt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljr8ztagt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:infinity-two-tone" {...props}></Icon>
