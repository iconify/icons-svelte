<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrd5ojx6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrd5ojx6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-plus" {...props}></Icon>
