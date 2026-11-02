<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe9k1ybro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe9k1ybro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:banknote-x-fill" {...props}></Icon>
