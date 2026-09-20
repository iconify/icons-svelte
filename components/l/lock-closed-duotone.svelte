<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwloscb6d.css';
import '../../css/t/tn4b2zsid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwloscb6d"/><path class="tn4b2zsid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:lock-closed-duotone" {...props}></Icon>
