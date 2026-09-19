<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydba-6b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ydba-6b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:facebook-alt-small" {...props}></Icon>
