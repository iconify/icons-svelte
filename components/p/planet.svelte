<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7l_i6bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7l_i6bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:planet" {...props}></Icon>
