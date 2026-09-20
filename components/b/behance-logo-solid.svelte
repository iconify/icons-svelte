<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g90jp1bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g90jp1bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:behance-logo-solid" {...props}></Icon>
