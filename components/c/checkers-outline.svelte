<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5kqz9n5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5kqz9n5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkers-outline" {...props}></Icon>
