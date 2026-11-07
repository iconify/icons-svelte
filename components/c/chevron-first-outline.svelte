<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyc9-xbym.css';
import '../../css/u/uou3acccj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyc9-xbym"/><path class="uou3acccj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevron-first-outline" {...props}></Icon>
