<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bodb8dxau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bodb8dxau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-moon-outline" {...props}></Icon>
