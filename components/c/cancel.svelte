<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h190_updm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h190_updm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cancel" {...props}></Icon>
