<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcibe0bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcibe0bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:comment-solid" {...props}></Icon>
