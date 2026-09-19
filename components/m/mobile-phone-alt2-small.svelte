<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvjgifbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dvjgifbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:mobile-phone-alt2-small" {...props}></Icon>
