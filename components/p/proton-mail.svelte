<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmn5w0e9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmn5w0e9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:proton-mail" {...props}></Icon>
