<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne9klnbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne9klnbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:help-scout" {...props}></Icon>
