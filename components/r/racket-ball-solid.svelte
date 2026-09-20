<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npoxn3bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npoxn3bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:racket-ball-solid" {...props}></Icon>
