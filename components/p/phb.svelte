<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apatysb6u.css';
import '../../css/s/sv53ehbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apatysb6u"/><path class="sv53ehbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:phb" {...props}></Icon>
