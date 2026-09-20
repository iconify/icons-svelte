<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrdhj80fb.css';
import '../../css/p/pob-y2b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrdhj80fb"/><path class="pob-y2b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:engagement" {...props}></Icon>
