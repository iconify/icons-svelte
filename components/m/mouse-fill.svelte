<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypfh2bccc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypfh2bccc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:mouse-fill" {...props}></Icon>
