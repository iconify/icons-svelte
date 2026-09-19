<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe513_xmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe513_xmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-up" {...props}></Icon>
