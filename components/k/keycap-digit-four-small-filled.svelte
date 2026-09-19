<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bym2xacxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bym2xacxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-four-small-filled" {...props}></Icon>
