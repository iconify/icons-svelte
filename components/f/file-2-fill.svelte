<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy6z9ubma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy6z9ubma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:file-2-fill" {...props}></Icon>
