<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gny9m6b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gny9m6b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:push-chevron-down" {...props}></Icon>
