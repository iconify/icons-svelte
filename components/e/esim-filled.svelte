<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js7ccfdti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js7ccfdti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:esim-filled" {...props}></Icon>
