<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1b-v8rmi.css';
import '../../css/w/whbeue6my.css';
import '../../css/a/at92h2-kh.css';
import '../../css/c/ch9w-bbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1b-v8rmi"/><path class="whbeue6my"/><path clip-rule="evenodd" class="at92h2-kh"/><path class="ch9w-bbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notification-lines-remove-bold-duotone" {...props}></Icon>
