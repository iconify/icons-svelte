<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hufrxye1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hufrxye1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:reactive-resume" {...props}></Icon>
