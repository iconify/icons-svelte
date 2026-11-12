<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i48ixpics.css';
import '../../css/q/q0dd0fvak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i48ixpics"/><path class="q0dd0fvak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dosvault-dark" {...props}></Icon>
