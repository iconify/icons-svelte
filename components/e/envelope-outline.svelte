<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjkr4gbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fjkr4gbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:envelope-outline" {...props}></Icon>
