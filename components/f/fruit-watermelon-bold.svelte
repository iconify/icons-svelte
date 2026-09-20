<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiyx6zbdr.css';
import '../../css/c/c03wv0hyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiyx6zbdr"/><path class="c03wv0hyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:fruit-watermelon-bold" {...props}></Icon>
