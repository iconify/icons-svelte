<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h66-e1jim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h66-e1jim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receipt5-filled" {...props}></Icon>
