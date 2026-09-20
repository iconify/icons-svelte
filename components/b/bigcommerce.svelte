<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy3n3v-_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy3n3v-_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bigcommerce" {...props}></Icon>
