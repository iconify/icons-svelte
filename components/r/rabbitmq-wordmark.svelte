<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u86l3ccfz.css';
import '../../css/b/b8bh25bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u86l3ccfz"/><path class="b8bh25bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:rabbitmq-wordmark" {...props}></Icon>
