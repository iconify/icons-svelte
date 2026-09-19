<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaed-9bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yaed-9bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:extension-alt" {...props}></Icon>
