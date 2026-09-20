<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-iyv7qyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-iyv7qyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-forms" {...props}></Icon>
