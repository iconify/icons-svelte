<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bckagbb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bckagbb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ease-in-out-solid" {...props}></Icon>
