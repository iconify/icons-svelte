<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4um3lh3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4um3lh3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:film-heart" {...props}></Icon>
