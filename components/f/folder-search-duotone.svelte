<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtpeb-edw.css';
import '../../css/m/mq2ccos5s.css';
import '../../css/w/wh25rpwfz.css';
import '../../css/u/us0mlcc8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="mq2ccos5s"/><path clip-rule="evenodd" class="wh25rpwfz"/></g><path clip-rule="evenodd" class="us0mlcc8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-search-duotone" {...props}></Icon>
