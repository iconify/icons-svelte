<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeu0v89pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeu0v89pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:medical-cross" {...props}></Icon>
