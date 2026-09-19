<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng0uf7b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":650,"height":679};
const content = `<path class="ng0uf7b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:hatenabookmark" {...props}></Icon>
