<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8p3tfo-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8p3tfo-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:label-filled" {...props}></Icon>
