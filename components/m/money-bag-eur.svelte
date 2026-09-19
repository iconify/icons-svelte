<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihf1r4aus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ihf1r4aus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:money-bag-eur" {...props}></Icon>
