<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h93r4zbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h93r4zbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email" {...props}></Icon>
