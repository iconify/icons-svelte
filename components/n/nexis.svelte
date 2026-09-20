<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk396rb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk396rb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nexis" {...props}></Icon>
