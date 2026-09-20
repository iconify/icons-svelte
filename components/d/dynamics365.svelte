<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd-ht8b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd-ht8b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dynamics365" {...props}></Icon>
