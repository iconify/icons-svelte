<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gojvx1bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gojvx1bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-menu-left" {...props}></Icon>
