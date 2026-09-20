<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt5qu0bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt5qu0bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:muller" {...props}></Icon>
