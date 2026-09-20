<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/w/wmlgyxqsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="bc1fd0lxe"/><path class="wmlgyxqsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ferrishare" {...props}></Icon>
