<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaihz8b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vaihz8b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-vertically-filled" {...props}></Icon>
