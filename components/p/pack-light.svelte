<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kylfzebuf.css';
import '../../css/i/impgh8bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kylfzebuf"/><path class="impgh8bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pack-light" {...props}></Icon>
