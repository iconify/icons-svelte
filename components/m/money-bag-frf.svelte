<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcq6pcbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wcq6pcbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:money-bag-frf" {...props}></Icon>
