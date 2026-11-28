<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdb7o4m6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdb7o4m6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bell-alert" {...props}></Icon>
