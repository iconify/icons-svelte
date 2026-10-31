<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki-dbhbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki-dbhbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-sparkle-fill-round" {...props}></Icon>
