<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6ldn1b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6ldn1b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cloud-off" {...props}></Icon>
