<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni68l2f_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni68l2f_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:keypad-fill" {...props}></Icon>
