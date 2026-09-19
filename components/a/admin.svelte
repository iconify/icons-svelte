<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjmqt5btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjmqt5btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:admin" {...props}></Icon>
