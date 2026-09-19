<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al29qccdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="al29qccdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rays" {...props}></Icon>
