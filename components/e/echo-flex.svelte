<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddf3uwy0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddf3uwy0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-flex" {...props}></Icon>
