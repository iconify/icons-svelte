<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diofki2lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="diofki2lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:linear-round" {...props}></Icon>
