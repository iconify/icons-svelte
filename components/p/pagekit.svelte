<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsmt7b2xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsmt7b2xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pagekit" {...props}></Icon>
