<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4wd_7bju.css';
import '../../css/w/wnjg76bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4wd_7bju"/><path class="wnjg76bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portainer-pink" {...props}></Icon>
