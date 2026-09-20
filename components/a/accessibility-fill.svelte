<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny6_5-aau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ny6_5-aau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:accessibility-fill" {...props}></Icon>
