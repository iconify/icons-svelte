<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osmjjhb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="osmjjhb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:drupal-wordmark" {...props}></Icon>
