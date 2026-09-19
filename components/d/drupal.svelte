<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohxk8dnoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohxk8dnoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:drupal" {...props}></Icon>
