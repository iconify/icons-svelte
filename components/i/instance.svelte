<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i534_nb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i534_nb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:instance" {...props}></Icon>
