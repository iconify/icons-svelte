<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg2xj8bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":101,"height":22};
const content = `<path class="vg2xj8bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:caldotcom-dark" {...props}></Icon>
