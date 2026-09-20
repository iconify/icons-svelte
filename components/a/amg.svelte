<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw73_wxno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw73_wxno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:amg" {...props}></Icon>
