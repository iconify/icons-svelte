<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjsf1xcyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjsf1xcyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:align-justify" {...props}></Icon>
