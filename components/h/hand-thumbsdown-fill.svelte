<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3y-a-e0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="g3y-a-e0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hand-thumbsdown-fill" {...props}></Icon>
