<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml9tklbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml9tklbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:home-assistant-community-store" {...props}></Icon>
