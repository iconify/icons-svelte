<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skod2vbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="skod2vbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:json-alt-4-fill" {...props}></Icon>
