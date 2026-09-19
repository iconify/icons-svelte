<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4y9y-bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4y9y-bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:code-bracket-square" {...props}></Icon>
