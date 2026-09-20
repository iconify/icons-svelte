<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozk_7lbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozk_7lbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:blockquote-fill" {...props}></Icon>
