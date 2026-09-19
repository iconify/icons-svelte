<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5_886_2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="c5_886_2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:layers-alt-fill" {...props}></Icon>
