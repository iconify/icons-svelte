<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3r70jbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="h3r70jbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:american-express" {...props}></Icon>
