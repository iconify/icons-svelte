<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go3e2fbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go3e2fbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chevron-right-small" {...props}></Icon>
