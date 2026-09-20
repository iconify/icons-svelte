<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c20pa821i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c20pa821i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:gold-flat" {...props}></Icon>
