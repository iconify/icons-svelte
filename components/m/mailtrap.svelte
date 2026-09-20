<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij04o4ern.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij04o4ern"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mailtrap" {...props}></Icon>
