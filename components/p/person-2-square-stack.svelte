<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw_5fmbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qw_5fmbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-2-square-stack" {...props}></Icon>
