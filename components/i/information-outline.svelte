<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzy55k3-q.css';
import '../../css/g/gtbk85xxx.css';
import '../../css/c/cfprd2egi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mzy55k3-q"/><path class="gtbk85xxx"/><path class="cfprd2egi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:information-outline" {...props}></Icon>
