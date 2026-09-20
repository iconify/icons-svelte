<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w970jmblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w970jmblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kando" {...props}></Icon>
