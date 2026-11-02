<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhvnvmb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhvnvmb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:partly-cloud-daytime-fill" {...props}></Icon>
