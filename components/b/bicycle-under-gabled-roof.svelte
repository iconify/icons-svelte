<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amqo51b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="amqo51b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-under-gabled-roof" {...props}></Icon>
