<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7-s-kbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7-s-kbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:humble-bundle" {...props}></Icon>
