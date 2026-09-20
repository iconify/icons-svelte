<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnq8zkb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rnq8zkb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:arrow-right-circle" {...props}></Icon>
