<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhwamkbws.css';
import '../../css/d/dtnoc5ijb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhwamkbws"/><path class="dtnoc5ijb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-arrow-up-duotone" {...props}></Icon>
