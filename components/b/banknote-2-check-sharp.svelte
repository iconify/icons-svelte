<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5zuveb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5zuveb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-2-check-sharp" {...props}></Icon>
