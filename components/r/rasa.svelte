<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0by00bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0by00bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rasa" {...props}></Icon>
