<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f67q75bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f67q75bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jetblue" {...props}></Icon>
