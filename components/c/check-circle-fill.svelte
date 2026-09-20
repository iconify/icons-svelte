<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b14kaei-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b14kaei-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:check-circle-fill" {...props}></Icon>
