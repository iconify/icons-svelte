<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icnknskoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icnknskoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:grapes" {...props}></Icon>
