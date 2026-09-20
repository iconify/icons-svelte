<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhwamkbws.css';
import '../../css/o/ox3sqx-4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhwamkbws"/><path class="ox3sqx-4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-arrow-down-duotone" {...props}></Icon>
