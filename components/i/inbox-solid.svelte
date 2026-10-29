<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlb4bxb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlb4bxb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:inbox-solid" {...props}></Icon>
