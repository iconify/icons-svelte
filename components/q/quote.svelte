<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2lxspncn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h2lxspncn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:quote" {...props}></Icon>
