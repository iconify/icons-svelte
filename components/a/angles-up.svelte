<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgl53ia8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgl53ia8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:angles-up" {...props}></Icon>
