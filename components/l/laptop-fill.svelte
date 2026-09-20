<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8lq571rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8lq571rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:laptop-fill" {...props}></Icon>
