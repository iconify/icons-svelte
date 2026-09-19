<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw4exoqzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gw4exoqzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ballot-box-with-check-small-filled" {...props}></Icon>
