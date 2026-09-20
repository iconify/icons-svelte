<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps4tf-iae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps4tf-iae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-twitter-filled" {...props}></Icon>
