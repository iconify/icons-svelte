<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g128-w4ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g128-w4ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pycharm-wordmark" {...props}></Icon>
