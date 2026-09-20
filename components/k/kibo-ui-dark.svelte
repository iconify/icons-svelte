<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngpo3ddrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":117,"height":116};
const content = `<path clip-rule="evenodd" class="ngpo3ddrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kibo-ui-dark" {...props}></Icon>
