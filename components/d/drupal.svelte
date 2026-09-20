<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fep9-3zrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="fep9-3zrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:drupal" {...props}></Icon>
