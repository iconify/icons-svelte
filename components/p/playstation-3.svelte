<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/talh9rb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="talh9rb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:playstation-3" {...props}></Icon>
