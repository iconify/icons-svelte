<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoeo5dh7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoeo5dh7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chevron-left-filled" {...props}></Icon>
