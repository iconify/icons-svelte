<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb43jsb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb43jsb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:download-offline-line" {...props}></Icon>
