<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1jf6ebeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1600};
const content = `<path class="e1jf6ebeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:html5" {...props}></Icon>
