<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m35tg7k6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m35tg7k6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:message-circle" {...props}></Icon>
