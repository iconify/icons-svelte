<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ry_ybrz.css';
import '../../css/b/b9icdeqxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ry_ybrz"/><path class="b9icdeqxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:envelope-flying" {...props}></Icon>
