<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjeh518qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vjeh518qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:droplet" {...props}></Icon>
