<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg421pbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg421pbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:inquirer" {...props}></Icon>
