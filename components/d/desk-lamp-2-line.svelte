<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6d1tt4vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6d1tt4vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:desk-lamp-2-line" {...props}></Icon>
