<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw7lxg0ts.css';
import '../../css/n/n7p431bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw7lxg0ts"/><path class="n7p431bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-dot-open-bold" {...props}></Icon>
