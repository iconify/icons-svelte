<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmjqf_1pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmjqf_1pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailchimp" {...props}></Icon>
