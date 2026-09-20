<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujfgtsigt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujfgtsigt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:grunt" {...props}></Icon>
