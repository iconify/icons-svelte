<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdkdn5bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdkdn5bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:medical" {...props}></Icon>
