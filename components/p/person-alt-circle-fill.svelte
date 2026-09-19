<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-d_8ghxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x-d_8ghxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-alt-circle-fill" {...props}></Icon>
