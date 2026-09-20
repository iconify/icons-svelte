<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boemwgzge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boemwgzge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:keypad-line" {...props}></Icon>
