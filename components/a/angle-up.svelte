<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9da430vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9da430vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:angle-up" {...props}></Icon>
