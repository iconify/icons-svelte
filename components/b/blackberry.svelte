<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5s-b_bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5s-b_bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:blackberry" {...props}></Icon>
