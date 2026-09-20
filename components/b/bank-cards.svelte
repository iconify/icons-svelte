<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2ihnjbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="k2ihnjbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:bank-cards" {...props}></Icon>
