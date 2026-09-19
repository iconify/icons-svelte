<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1gf3kb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1gf3kb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:envelope-open-outline" {...props}></Icon>
