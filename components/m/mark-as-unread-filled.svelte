<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emh9t9b8k.css';
import '../../css/t/tvods8eyi.css';
import '../../css/h/hidh8db6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emh9t9b8k"/><path class="tvods8eyi"/><path class="hidh8db6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mark-as-unread-filled" {...props}></Icon>
