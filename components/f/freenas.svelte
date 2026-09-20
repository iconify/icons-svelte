<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9k372bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9k372bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:freenas" {...props}></Icon>
