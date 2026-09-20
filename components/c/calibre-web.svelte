<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1yen-bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1yen-bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:calibre-web" {...props}></Icon>
