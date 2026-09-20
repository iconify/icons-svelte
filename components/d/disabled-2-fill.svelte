<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm723rb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm723rb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:disabled-2-fill" {...props}></Icon>
