<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgtz7qjon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgtz7qjon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:banknote-check" {...props}></Icon>
