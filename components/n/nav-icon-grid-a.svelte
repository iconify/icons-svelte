<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvko1jboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="hvko1jboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:nav-icon-grid-a" {...props}></Icon>
