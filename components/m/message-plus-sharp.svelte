<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuqflabyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuqflabyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-plus-sharp" {...props}></Icon>
