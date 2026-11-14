<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxrezvvow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxrezvvow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:credit-card-pos" {...props}></Icon>
