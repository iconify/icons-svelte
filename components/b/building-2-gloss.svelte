<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wym4_cc3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wym4_cc3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:building-2-gloss" {...props}></Icon>
