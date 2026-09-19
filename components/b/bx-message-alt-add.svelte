<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8ezhpb5o.css';
import '../../css/c/ch6_fcbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8ezhpb5o"/><path class="ch6_fcbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-message-alt-add" {...props}></Icon>
