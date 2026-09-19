<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iexxgd58y.css';
import '../../css/x/x8r3bo3uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iexxgd58y"/><path class="x8r3bo3uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:microservices-1" {...props}></Icon>
