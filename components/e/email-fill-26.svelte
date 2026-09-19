<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib8412b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ib8412b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:email-fill-26" {...props}></Icon>
