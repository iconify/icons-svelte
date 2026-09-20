<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7j9a7h-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7j9a7h-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:act" {...props}></Icon>
