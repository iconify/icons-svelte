<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uer8hib0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uer8hib0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:modrinth" {...props}></Icon>
