<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr1hukzzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr1hukzzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gnu-privacy-guard" {...props}></Icon>
