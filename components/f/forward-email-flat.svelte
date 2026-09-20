<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyu1mvble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cyu1mvble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:forward-email-flat" {...props}></Icon>
