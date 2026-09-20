<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muph4f-qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muph4f-qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:house-alt-filled" {...props}></Icon>
