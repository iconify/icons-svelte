<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhj-ll95a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhj-ll95a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pre-commit" {...props}></Icon>
