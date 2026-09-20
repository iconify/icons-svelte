<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iis8z6o6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iis8z6o6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nextdns" {...props}></Icon>
