<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu631ubgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu631ubgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:office-building" {...props}></Icon>
