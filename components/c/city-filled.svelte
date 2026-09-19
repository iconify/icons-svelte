<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s89b7sskt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s89b7sskt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:city-filled" {...props}></Icon>
