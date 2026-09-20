<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db2z1jbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db2z1jbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-paragraph" {...props}></Icon>
