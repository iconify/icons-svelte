<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za2ck5ubr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="za2ck5ubr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:character" {...props}></Icon>
