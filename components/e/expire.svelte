<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yza2zs_of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yza2zs_of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:expire" {...props}></Icon>
