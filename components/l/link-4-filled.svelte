<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdrz6jbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdrz6jbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:link-4-filled" {...props}></Icon>
