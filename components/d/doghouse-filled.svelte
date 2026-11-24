<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd9s1hbcj.css';
import '../../css/m/m4hvdnqig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gd9s1hbcj"/><path class="m4hvdnqig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:doghouse-filled" {...props}></Icon>
