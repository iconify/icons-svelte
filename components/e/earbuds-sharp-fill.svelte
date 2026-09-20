<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e32ell92q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e32ell92q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:earbuds-sharp-fill" {...props}></Icon>
