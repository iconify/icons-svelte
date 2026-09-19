<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1al5gu-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t1al5gu-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:eventbrite" {...props}></Icon>
