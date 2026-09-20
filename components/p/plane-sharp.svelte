<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-6ekh5os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-6ekh5os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plane-sharp" {...props}></Icon>
