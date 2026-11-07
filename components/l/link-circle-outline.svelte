<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae_fwibxk.css';
import '../../css/a/a_tf9kbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae_fwibxk"/><path class="a_tf9kbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-circle-outline" {...props}></Icon>
