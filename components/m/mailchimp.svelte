<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t805-accq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t805-accq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mailchimp" {...props}></Icon>
