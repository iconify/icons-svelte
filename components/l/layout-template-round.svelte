<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej73ggbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej73ggbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layout-template-round" {...props}></Icon>
