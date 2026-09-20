<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgz36-2oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgz36-2oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mailchimp" {...props}></Icon>
