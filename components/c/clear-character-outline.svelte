<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvn5f30vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvn5f30vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:clear-character-outline" {...props}></Icon>
