<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv4cjgadb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv4cjgadb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pagespeed-insights" {...props}></Icon>
