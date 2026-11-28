<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upq40fb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upq40fb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-info" {...props}></Icon>
