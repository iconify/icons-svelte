<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsqb0y01i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsqb0y01i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:github-alt" {...props}></Icon>
