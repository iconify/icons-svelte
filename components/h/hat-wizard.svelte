<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7adn7brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c7adn7brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hat-wizard" {...props}></Icon>
