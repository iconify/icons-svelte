<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifhxd1b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifhxd1b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-lines-sharp-fill" {...props}></Icon>
