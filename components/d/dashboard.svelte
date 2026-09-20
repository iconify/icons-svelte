<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mszzedjss.css';
import '../../css/s/s5a196bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mszzedjss"/><path class="s5a196bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:dashboard" {...props}></Icon>
