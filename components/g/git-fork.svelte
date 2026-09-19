<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1ofj0jgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ofj0jgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:git-fork" {...props}></Icon>
