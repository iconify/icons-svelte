<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls4o5rx5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls4o5rx5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-right-to-line-fill" {...props}></Icon>
