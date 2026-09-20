<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aomeu167z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aomeu167z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-square-fill" {...props}></Icon>
