<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mphqjt4dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mphqjt4dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-11" {...props}></Icon>
