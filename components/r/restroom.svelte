<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlbc19srw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vlbc19srw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:restroom" {...props}></Icon>
