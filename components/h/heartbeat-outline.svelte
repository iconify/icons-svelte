<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1bf0p4rg.css';
import '../../css/g/gf6bg710v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1bf0p4rg"/><path class="gf6bg710v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:heartbeat-outline" {...props}></Icon>
