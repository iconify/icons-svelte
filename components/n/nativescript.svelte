<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfo45p3ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfo45p3ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nativescript" {...props}></Icon>
