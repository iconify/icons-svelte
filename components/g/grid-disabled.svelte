<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu23hiv_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wu23hiv_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:grid-disabled" {...props}></Icon>
