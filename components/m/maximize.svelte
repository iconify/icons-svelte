<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9jsx66hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9jsx66hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:maximize" {...props}></Icon>
