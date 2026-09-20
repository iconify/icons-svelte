<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aghg-24qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aghg-24qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hat-cowboy" {...props}></Icon>
