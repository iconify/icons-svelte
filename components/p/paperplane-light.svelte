<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gren7lhvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gren7lhvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:paperplane-light" {...props}></Icon>
