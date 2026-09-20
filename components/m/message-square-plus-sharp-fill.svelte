<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im5jvnb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im5jvnb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-plus-sharp-fill" {...props}></Icon>
