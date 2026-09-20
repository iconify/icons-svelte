<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxr8a6byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxr8a6byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:actix" {...props}></Icon>
