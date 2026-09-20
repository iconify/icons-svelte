<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f540g9cop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f540g9cop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-5-sharp" {...props}></Icon>
