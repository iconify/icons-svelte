<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlro6pcld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qlro6pcld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hands-support" {...props}></Icon>
