<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj0p3sbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj0p3sbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:banknote-minus" {...props}></Icon>
