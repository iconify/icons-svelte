<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiw79xjwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiw79xjwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bath-filled" {...props}></Icon>
