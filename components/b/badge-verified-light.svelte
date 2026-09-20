<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvndr4bzf.css';
import '../../css/n/nifei5b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvndr4bzf"/><path class="nifei5b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:badge-verified-light" {...props}></Icon>
