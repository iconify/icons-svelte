<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx8yl6bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx8yl6bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:blogger" {...props}></Icon>
