<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3f_98t8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3f_98t8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-openoffice" {...props}></Icon>
