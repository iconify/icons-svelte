<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rytk8ivix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rytk8ivix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bookmark-24" {...props}></Icon>
