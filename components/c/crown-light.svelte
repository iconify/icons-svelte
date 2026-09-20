<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrz7kf1gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrz7kf1gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:crown-light" {...props}></Icon>
