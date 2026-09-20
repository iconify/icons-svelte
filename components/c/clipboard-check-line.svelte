<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fae7j8bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fae7j8bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clipboard-check-line" {...props}></Icon>
