<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ormpdu8ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ormpdu8ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:rewind-right-outline" {...props}></Icon>
