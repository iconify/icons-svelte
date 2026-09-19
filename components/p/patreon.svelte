<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgx-9abtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgx-9abtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:patreon" {...props}></Icon>
