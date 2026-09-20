<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-jo04stb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v-jo04stb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:json-document-filled" {...props}></Icon>
