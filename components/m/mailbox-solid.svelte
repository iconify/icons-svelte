<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaa1sl7cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaa1sl7cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mailbox-solid" {...props}></Icon>
