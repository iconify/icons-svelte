<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93c9qvzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o93c9qvzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:mouse-alt-2" {...props}></Icon>
