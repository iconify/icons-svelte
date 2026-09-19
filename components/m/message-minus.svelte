<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go9b1n-cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go9b1n-cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:message-minus" {...props}></Icon>
