<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w43uqtbnn.css';
import '../../css/p/pzgd11spf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w43uqtbnn"/><path clip-rule="evenodd" class="pzgd11spf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hashtag-circle-bold" {...props}></Icon>
