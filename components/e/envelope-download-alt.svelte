<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok8dtubfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok8dtubfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-download-alt" {...props}></Icon>
