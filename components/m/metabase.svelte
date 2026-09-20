<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsh0a7b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsh0a7b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:metabase" {...props}></Icon>
