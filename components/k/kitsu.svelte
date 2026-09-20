<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4u66kbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4u66kbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kitsu" {...props}></Icon>
