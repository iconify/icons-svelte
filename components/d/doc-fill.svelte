<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ashe6sbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ashe6sbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-fill" {...props}></Icon>
