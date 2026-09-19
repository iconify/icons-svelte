<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6y_uvb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6y_uvb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:lightning-bolt" {...props}></Icon>
