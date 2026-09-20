<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9r16rguq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9r16rguq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dynatrace" {...props}></Icon>
