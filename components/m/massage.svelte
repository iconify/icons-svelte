<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm21awbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm21awbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:massage" {...props}></Icon>
