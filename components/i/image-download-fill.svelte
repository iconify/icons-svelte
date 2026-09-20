<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzs07zk9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzs07zk9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-download-fill" {...props}></Icon>
