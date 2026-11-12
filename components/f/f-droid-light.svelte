<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um9s7iazo.css';
import '../../css/f/fo7w_pq-j.css';
import '../../css/f/f7wi88xzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="um9s7iazo"/><path class="fo7w_pq-j"/><path class="f7wi88xzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:f-droid-light" {...props}></Icon>
