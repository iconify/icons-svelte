<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ely0apt9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ely0apt9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:espocrm-dark" {...props}></Icon>
