<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch-9y_2zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ch-9y_2zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rabbitmq-dark" {...props}></Icon>
