<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biybr5bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="biybr5bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:chevron-right" {...props}></Icon>
