<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9s-4iwjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9s-4iwjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-muted-vert-circle-line" {...props}></Icon>
