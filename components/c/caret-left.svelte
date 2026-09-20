<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faph03-kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faph03-kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:caret-left" {...props}></Icon>
