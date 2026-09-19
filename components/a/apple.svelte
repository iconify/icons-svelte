<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmoh75oro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="hmoh75oro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:apple" {...props}></Icon>
