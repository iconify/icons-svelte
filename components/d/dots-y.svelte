<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-ke-cb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q-ke-cb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:dots-y" {...props}></Icon>
