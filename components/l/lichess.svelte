<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uelzpbbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uelzpbbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lichess" {...props}></Icon>
