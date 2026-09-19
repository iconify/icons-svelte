<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li9b89bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="li9b89bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hand-peace" {...props}></Icon>
