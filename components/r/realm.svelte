<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiqt0cbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiqt0cbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:realm" {...props}></Icon>
