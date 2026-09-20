<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz8z7jozz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz8z7jozz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pdq" {...props}></Icon>
