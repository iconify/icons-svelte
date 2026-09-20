<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8eaf2bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path clip-rule="evenodd" class="s8eaf2bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:github-light" {...props}></Icon>
