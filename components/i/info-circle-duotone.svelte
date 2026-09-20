<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l57giywpk.css';
import '../../css/f/fue51nqfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l57giywpk"/><path class="fue51nqfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:info-circle-duotone" {...props}></Icon>
