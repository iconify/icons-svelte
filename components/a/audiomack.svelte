<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp847_bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp847_bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:audiomack" {...props}></Icon>
