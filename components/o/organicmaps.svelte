<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4y7eublc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4y7eublc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:organicmaps" {...props}></Icon>
