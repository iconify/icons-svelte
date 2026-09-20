<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq4ywbbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq4ywbbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:datocms" {...props}></Icon>
