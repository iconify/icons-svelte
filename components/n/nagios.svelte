<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd3noewjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":51.89,"height":64,"left":4.66,"top":-1.4};
const content = `<path class="wd3noewjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nagios" {...props}></Icon>
