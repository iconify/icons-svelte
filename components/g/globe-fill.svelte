<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dttqe79at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dttqe79at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:globe-fill" {...props}></Icon>
