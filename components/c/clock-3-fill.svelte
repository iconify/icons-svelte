<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4ex10bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g4ex10bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-3-fill" {...props}></Icon>
