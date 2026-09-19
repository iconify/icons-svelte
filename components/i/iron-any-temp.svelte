<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fss3asbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="fss3asbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:iron-any-temp" {...props}></Icon>
