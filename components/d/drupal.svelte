<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa4p5bdyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aa4p5bdyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:drupal" {...props}></Icon>
