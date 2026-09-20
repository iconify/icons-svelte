<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptj-h9xbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptj-h9xbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:npm" {...props}></Icon>
