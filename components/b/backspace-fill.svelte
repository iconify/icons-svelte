<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae9euyb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ae9euyb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:backspace-fill" {...props}></Icon>
