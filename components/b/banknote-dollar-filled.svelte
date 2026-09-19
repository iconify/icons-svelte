<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h34m3h0js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h34m3h0js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:banknote-dollar-filled" {...props}></Icon>
