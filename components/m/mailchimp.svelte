<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzmadub0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="rzmadub0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:mailchimp" {...props}></Icon>
