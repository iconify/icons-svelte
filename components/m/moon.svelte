<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qey9m29-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qey9m29-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:moon" {...props}></Icon>
