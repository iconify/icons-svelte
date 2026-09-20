<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdzajkb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdzajkb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flag-line" {...props}></Icon>
