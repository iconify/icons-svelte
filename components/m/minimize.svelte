<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr_ygns4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lr_ygns4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:minimize" {...props}></Icon>
