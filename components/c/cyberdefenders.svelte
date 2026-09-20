<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1t1l7b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1t1l7b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cyberdefenders" {...props}></Icon>
