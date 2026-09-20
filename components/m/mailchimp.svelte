<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgspm5e_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hgspm5e_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mailchimp" {...props}></Icon>
