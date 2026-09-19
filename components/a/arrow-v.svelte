<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijj-5e42m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijj-5e42m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:arrow-v" {...props}></Icon>
