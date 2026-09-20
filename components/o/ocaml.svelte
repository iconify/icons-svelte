<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef7--8bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef7--8bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ocaml" {...props}></Icon>
