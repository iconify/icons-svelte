<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt-sfhuza.css';
import '../../css/x/x8r3bo3uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nt-sfhuza"/><path class="x8r3bo3uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:microservices-2" {...props}></Icon>
