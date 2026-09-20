<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dih82-bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":290,"height":79};
const content = `<path clip-rule="evenodd" class="dih82-bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:polygon-io-dark" {...props}></Icon>
