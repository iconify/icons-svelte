<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-idq0lhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-idq0lhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:embarcadero" {...props}></Icon>
