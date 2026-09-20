<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj80bmbzo.css';
import '../../css/s/s4vpxwbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj80bmbzo"/><path class="s4vpxwbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:plan-light" {...props}></Icon>
