<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zekao-5lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zekao-5lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:adminer" {...props}></Icon>
