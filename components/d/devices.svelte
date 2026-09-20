<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghvfc0l6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ghvfc0l6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:devices" {...props}></Icon>
