<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm_5gd4wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm_5gd4wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-outgoing-fill" {...props}></Icon>
