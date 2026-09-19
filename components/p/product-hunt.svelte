<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivvrc5b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivvrc5b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:product-hunt" {...props}></Icon>
