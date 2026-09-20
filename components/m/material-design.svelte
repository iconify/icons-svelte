<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p83gi2tbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p83gi2tbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:material-design" {...props}></Icon>
