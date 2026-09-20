<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi4e96bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi4e96bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-repository-commits-line" {...props}></Icon>
