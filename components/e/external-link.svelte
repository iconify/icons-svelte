<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7vb09_my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7vb09_my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:external-link" {...props}></Icon>
