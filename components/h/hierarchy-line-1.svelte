<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbncxqbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbncxqbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hierarchy-line-1" {...props}></Icon>
